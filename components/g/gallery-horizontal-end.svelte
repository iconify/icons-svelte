<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1lo5lbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1lo5lbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gallery-horizontal-end" {...props}></Icon>
