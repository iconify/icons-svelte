<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3h3sv7mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3h3sv7mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-s-2-line" {...props}></Icon>
