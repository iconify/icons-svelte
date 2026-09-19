<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbfd9416o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbfd9416o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-volume-low" {...props}></Icon>
