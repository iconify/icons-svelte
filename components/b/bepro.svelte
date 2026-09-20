<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7m_bcgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az7m_bcgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bepro" {...props}></Icon>
