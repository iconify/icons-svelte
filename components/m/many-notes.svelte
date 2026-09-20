<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o90f_1ibj.css';
import '../../css/t/t33cxfb4q.css';
import '../../css/z/z4nxktxkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o90f_1ibj"/><path class="t33cxfb4q"/><path class="z4nxktxkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:many-notes" {...props}></Icon>
