<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqrd0s_-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqrd0s_-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:filter-linear" {...props}></Icon>
