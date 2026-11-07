<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn7wcebed.css';
import '../../css/e/eswrkkbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn7wcebed"/><path class="eswrkkbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:double-alt-arrow-down-bold" {...props}></Icon>
