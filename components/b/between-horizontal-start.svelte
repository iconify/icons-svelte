<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nilgi0bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nilgi0bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:between-horizontal-start" {...props}></Icon>
