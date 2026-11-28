<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_ok3bclj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ok3bclj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:align-vertical-space-between-solid" {...props}></Icon>
