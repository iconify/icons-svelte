<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_26-gegh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_26-gegh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ladder-line" {...props}></Icon>
