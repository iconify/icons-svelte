<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpd41eeny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpd41eeny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pig-fill" {...props}></Icon>
