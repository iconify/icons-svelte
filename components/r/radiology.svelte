<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2x7t-b5p.css';
import '../../css/i/i9nyku57s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="v2x7t-b5p"/><path class="i9nyku57s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:radiology" {...props}></Icon>
