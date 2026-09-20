<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1ibgbpxi.css';
import '../../css/z/zvg05gx_g.css';
import '../../css/d/d4-m_ebkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ibgbpxi"/><path class="zvg05gx_g"/><path class="d4-m_ebkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:hipchat" {...props}></Icon>
