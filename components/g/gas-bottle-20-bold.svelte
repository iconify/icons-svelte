<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrwndsbwa.css';
import '../../css/e/ea6-embbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wrwndsbwa"/><path class="ea6-embbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-bottle-20-bold" {...props}></Icon>
