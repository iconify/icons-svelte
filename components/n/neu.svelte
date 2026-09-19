<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxkjwvbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nxkjwvbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:neu" {...props}></Icon>
