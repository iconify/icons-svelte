<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok3gm7bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok3gm7bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-horizontal-linear" {...props}></Icon>
