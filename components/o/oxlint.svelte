<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu03a2h3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yu03a2h3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:oxlint" {...props}></Icon>
