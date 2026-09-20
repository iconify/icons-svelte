<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijt4jib4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijt4jib4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codefactor-logo-solid" {...props}></Icon>
