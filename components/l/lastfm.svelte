<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3mazih7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f3mazih7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:lastfm" {...props}></Icon>
