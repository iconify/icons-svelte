<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svo32d08a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="svo32d08a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-checkbox-checked" {...props}></Icon>
