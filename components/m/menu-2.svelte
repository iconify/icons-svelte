<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz2_1m_at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz2_1m_at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:menu-2" {...props}></Icon>
