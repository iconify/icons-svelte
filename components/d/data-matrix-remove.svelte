<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0c396fkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0c396fkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:data-matrix-remove" {...props}></Icon>
