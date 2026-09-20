<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6r-1bcyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6r-1bcyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-plus-fill" {...props}></Icon>
