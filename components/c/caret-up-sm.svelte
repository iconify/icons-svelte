<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oppwr_pjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oppwr_pjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:caret-up-sm" {...props}></Icon>
