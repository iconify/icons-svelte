<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqfyp56nr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqfyp56nr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:medication" {...props}></Icon>
