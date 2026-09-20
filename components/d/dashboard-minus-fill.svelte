<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb4mr0b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb4mr0b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-minus-fill" {...props}></Icon>
