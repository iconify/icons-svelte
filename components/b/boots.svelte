<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea3x4_mfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea3x4_mfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:boots" {...props}></Icon>
