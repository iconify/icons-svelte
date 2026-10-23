<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_ycwfbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_ycwfbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bookmark" {...props}></Icon>
