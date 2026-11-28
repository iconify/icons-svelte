<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym7_kkb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym7_kkb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:puzzle-check-solid" {...props}></Icon>
