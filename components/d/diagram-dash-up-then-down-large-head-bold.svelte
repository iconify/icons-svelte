<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj9vmwbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nj9vmwbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-dash-up-then-down-large-head-bold" {...props}></Icon>
