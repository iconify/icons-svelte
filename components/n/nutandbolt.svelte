<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypu5ngbio.css';
import '../../css/i/i2t1upb9f.css';
import '../../css/w/wazoh8bmu.css';
import '../../css/z/zj07nkhgf.css';
import '../../css/p/p55k-ub0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ypu5ngbio"/><path class="i2t1upb9f"/><path class="wazoh8bmu"/><path class="zj07nkhgf"/><path class="p55k-ub0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nutandbolt" {...props}></Icon>
