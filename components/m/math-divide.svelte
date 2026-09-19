<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbxswfbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbxswfbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:math-divide" {...props}></Icon>
