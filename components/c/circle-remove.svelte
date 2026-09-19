<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtyy-2w-p.css';
import '../../css/q/qds-v0bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtyy-2w-p"/><path class="qds-v0bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-remove" {...props}></Icon>
