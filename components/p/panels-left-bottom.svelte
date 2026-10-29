<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ae-5w3bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae-5w3bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panels-left-bottom" {...props}></Icon>
