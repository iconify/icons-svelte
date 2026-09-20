<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy2k2q1_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy2k2q1_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:k3s" {...props}></Icon>
