<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqs9nibzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqs9nibzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:information-off-fill" {...props}></Icon>
