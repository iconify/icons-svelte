<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0esbbubm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0esbbubm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:align-left-1" {...props}></Icon>
