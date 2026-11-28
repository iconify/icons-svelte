<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0c-0nbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0c-0nbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-through-line-solid" {...props}></Icon>
