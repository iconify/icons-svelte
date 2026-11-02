<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8es5bcrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8es5bcrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lasso-fill" {...props}></Icon>
