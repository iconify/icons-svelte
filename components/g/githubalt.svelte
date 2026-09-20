<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a53id44pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a53id44pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:githubalt" {...props}></Icon>
