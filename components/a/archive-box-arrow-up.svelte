<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idkbwbbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idkbwbbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:archive-box-arrow-up" {...props}></Icon>
