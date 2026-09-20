<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3f0a4bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i3f0a4bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-scan-outline" {...props}></Icon>
