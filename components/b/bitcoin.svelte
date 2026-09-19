<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm39c7bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="xm39c7bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bitcoin" {...props}></Icon>
