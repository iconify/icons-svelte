<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saeo7x0bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="saeo7x0bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:browser" {...props}></Icon>
