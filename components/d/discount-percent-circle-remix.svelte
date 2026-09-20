<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-vsk4bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e-vsk4bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:discount-percent-circle-remix" {...props}></Icon>
