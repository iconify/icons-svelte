<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn6krnluk.css';
import '../../css/x/xlghf-tyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wn6krnluk"/><path class="xlghf-tyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:discussion-filled" {...props}></Icon>
