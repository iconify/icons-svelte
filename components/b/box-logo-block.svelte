<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr6j1u4ju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rr6j1u4ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:box-logo-block" {...props}></Icon>
