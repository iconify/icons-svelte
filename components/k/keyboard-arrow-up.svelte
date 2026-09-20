<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibz29_uar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibz29_uar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-arrow-up" {...props}></Icon>
