<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao3l91_rp.css';
import '../../css/y/yc4_t_bsz.css';
import '../../css/y/ygr30c8ly.css';
import '../../css/m/m_alf_hon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ao3l91_rp"/><path class="yc4_t_bsz"/><path class="ygr30c8ly"/><path class="m_alf_hon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cold-storage-20-bold" {...props}></Icon>
