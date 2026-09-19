<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0bly_bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":336,"height":614};
const content = `<path class="d0bly_bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:endash" {...props}></Icon>
