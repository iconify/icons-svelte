<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh59gvbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh59gvbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-text-center" {...props}></Icon>
