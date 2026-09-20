<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c927qnbfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c927qnbfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:church" {...props}></Icon>
