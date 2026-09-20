<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9v5viccb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="z9v5viccb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:mail-remove" {...props}></Icon>
