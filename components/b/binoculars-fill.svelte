<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssqkpgb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssqkpgb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:binoculars-fill" {...props}></Icon>
