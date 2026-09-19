<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0allnbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0allnbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-square-filled" {...props}></Icon>
