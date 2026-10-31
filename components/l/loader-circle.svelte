<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvlpiabmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvlpiabmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:loader-circle" {...props}></Icon>
