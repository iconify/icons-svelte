<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjgc4qb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjgc4qb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-column-decreasing-fill" {...props}></Icon>
