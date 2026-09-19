<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbx_8bbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="jbx_8bbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:collapse-content" {...props}></Icon>
