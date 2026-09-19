<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvy83nzau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvy83nzau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-no-signal" {...props}></Icon>
