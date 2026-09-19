<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o289ctp6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o289ctp6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-txt" {...props}></Icon>
