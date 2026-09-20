<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cf1_tib4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cf1_tib4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:path-logo" {...props}></Icon>
