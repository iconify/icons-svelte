<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu908ebyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu908ebyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-z-a" {...props}></Icon>
