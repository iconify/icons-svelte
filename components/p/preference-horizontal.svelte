<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/likitrbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="likitrbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:preference-horizontal" {...props}></Icon>
