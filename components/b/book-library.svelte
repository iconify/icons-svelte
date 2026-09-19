<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpct6ubfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpct6ubfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-library" {...props}></Icon>
