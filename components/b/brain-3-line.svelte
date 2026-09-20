<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsqdo2byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsqdo2byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-3-line" {...props}></Icon>
