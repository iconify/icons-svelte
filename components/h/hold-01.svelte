<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq8h0v79p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rq8h0v79p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hold-01" {...props}></Icon>
