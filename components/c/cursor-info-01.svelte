<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_m_eb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2_m_eb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-info-01" {...props}></Icon>
