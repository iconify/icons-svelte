<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf-283b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf-283b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-caret-right-circle" {...props}></Icon>
