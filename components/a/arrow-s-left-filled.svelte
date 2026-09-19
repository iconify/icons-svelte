<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k810wbbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k810wbbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-s-left-filled" {...props}></Icon>
