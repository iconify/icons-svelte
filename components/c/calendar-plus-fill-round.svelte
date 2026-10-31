<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3o9lkqqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3o9lkqqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-plus-fill-round" {...props}></Icon>
