<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zj3ej9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zj3ej9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:code" {...props}></Icon>
