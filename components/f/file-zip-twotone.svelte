<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xruktb97h.css';
import '../../css/c/czrbmi21p.css';
import '../../css/i/igyl9v99d.css';
import '../../css/o/osn79cbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xruktb97h"/><path class="czrbmi21p"/><path class="igyl9v99d"/><path class="osn79cbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-zip-twotone" {...props}></Icon>
