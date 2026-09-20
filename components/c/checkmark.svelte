<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2b1khblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2b1khblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:checkmark" {...props}></Icon>
