<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqvdm-b2t.css';
import '../../css/m/m_u6hpbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqvdm-b2t"/><path class="m_u6hpbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:padlock" {...props}></Icon>
