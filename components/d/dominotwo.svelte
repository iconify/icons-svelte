<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywv-5vb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":961,"height":960};
const content = `<path class="ywv-5vb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dominotwo" {...props}></Icon>
