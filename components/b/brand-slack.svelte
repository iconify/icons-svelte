<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di-4csbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="di-4csbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-slack" {...props}></Icon>
