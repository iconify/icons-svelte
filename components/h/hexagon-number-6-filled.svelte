<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh1m32rea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1m32rea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon-number-6-filled" {...props}></Icon>
