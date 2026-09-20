<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2v-wj12u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y2v-wj12u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-bar-decreasing" {...props}></Icon>
