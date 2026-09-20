<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edvt8ugrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edvt8ugrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:airtel" {...props}></Icon>
