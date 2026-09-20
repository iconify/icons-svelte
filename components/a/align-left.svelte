<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhnso0b1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhnso0b1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:align-left" {...props}></Icon>
