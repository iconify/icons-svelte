<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_2f6ubtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2f6ubtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-front-fill" {...props}></Icon>
