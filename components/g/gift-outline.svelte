<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knf-jaczf.css';
import '../../css/z/zakcsrw3t.css';
import '../../css/m/m_hfkybog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="knf-jaczf"/><rect class="zakcsrw3t"/><path class="m_hfkybog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:gift-outline" {...props}></Icon>
