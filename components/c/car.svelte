<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvb8-3kxm.css';
import '../../css/z/zyi21ccro.css';
import '../../css/a/acldr0b1s.css';
import '../../css/p/p2a9m_-0g.css';
import '../../css/b/bmekwzbyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvb8-3kxm"/><path class="zyi21ccro"/><path class="acldr0b1s"/><path class="p2a9m_-0g"/><path class="bmekwzbyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:car" {...props}></Icon>
