<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufy6p9byo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufy6p9byo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-connect-wifi" {...props}></Icon>
