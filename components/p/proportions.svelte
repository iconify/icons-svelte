<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2xw-0bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2xw-0bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:proportions" {...props}></Icon>
