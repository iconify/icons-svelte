<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz5k5b0_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lz5k5b0_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cat-sitting-and-whistle" {...props}></Icon>
