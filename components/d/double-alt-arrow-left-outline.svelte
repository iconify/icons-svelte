<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3_suq6hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d3_suq6hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-left-outline" {...props}></Icon>
