<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg6q7_b9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kg6q7_b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:battery-full-filled" {...props}></Icon>
