<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_h0j5bwz.css';
import '../../css/o/o27nl8m4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m_h0j5bwz"/><path clip-rule="evenodd" class="o27nl8m4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:kubernetes" {...props}></Icon>
