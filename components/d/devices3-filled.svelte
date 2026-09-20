<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8u9m_bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8u9m_bvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:devices3-filled" {...props}></Icon>
