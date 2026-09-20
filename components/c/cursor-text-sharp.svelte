<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajs828bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajs828bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-text-sharp" {...props}></Icon>
