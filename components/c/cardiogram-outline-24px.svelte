<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu5w9ebgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu5w9ebgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:cardiogram-outline-24px" {...props}></Icon>
