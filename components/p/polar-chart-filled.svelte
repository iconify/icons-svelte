<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7661-8qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7661-8qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:polar-chart-filled" {...props}></Icon>
