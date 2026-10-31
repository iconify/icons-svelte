<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffqf-bcny.css';
import '../../css/h/hfvyt7wet.css';
import '../../css/r/ro5dzvm8q.css';
import '../../css/m/mtqez028s.css';
import '../../css/z/zb8vxet2v.css';
import '../../css/k/kkrxhhbnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ffqf-bcny"/><path class="hfvyt7wet"/><path class="ro5dzvm8q"/><path class="mtqez028s"/><path class="zb8vxet2v"/><path class="kkrxhhbnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:cilantro" {...props}></Icon>
