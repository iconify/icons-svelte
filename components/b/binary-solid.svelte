<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0lrnldgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0lrnldgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:binary-solid" {...props}></Icon>
