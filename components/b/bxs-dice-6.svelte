<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awmipqbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awmipqbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dice-6" {...props}></Icon>
