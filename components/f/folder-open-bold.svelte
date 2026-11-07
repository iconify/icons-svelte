<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmlcj5izr.css';
import '../../css/q/qkmo0ac8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmlcj5izr"/><path clip-rule="evenodd" class="qkmo0ac8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-open-bold" {...props}></Icon>
