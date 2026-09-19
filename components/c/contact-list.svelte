<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1a3txb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="i1a3txb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:contact-list" {...props}></Icon>
