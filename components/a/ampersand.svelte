<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l286_mbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l286_mbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ampersand" {...props}></Icon>
