<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rppm-nbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rppm-nbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monitor-pause" {...props}></Icon>
