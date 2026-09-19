<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci15di65n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci15di65n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-award" {...props}></Icon>
