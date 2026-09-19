<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2fi3fe4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="y2fi3fe4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:copy-edit" {...props}></Icon>
