<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfud_4szt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfud_4szt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:binoculars-line" {...props}></Icon>
