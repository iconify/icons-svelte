<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyndi6n7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pyndi6n7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:presentation-chart" {...props}></Icon>
