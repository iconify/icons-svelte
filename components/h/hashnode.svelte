<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw4634b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw4634b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hashnode" {...props}></Icon>
