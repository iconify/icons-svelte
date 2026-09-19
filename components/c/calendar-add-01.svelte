<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_kgj_bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_kgj_bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-add-01" {...props}></Icon>
