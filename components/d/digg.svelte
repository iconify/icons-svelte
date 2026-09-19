<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3v7ddcmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="b3v7ddcmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:digg" {...props}></Icon>
