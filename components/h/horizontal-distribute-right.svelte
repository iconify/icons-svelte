<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d14e_qb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d14e_qb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:horizontal-distribute-right" {...props}></Icon>
