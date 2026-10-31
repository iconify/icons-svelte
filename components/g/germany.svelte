<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi1m_fwmt.css';
import '../../css/y/y55zcjfsz.css';
import '../../css/a/a_hbmibzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="bi1m_fwmt"/><path class="y55zcjfsz"/><path class="a_hbmibzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:germany" {...props}></Icon>
