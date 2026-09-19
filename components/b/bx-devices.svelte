<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2k-qb92l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2k-qb92l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-devices" {...props}></Icon>
