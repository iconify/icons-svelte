<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/y/yt1sn-2sn.css';
import '../../css/o/oisne4m_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="yt1sn-2sn"/><path class="oisne4m_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:euro" {...props}></Icon>
