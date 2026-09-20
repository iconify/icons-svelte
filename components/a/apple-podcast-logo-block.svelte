<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iymvk1-up.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iymvk1-up"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:apple-podcast-logo-block" {...props}></Icon>
