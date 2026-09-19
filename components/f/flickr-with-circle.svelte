<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqyo_428x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqyo_428x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:flickr-with-circle" {...props}></Icon>
