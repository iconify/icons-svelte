<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqrr3e9vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqrr3e9vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-column-decreasing-fill" {...props}></Icon>
