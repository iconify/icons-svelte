<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvr969ois.css';
import '../../css/w/wuqa13gqk.css';
import '../../css/w/wsyyf2bqs.css';
import '../../css/q/qw_fs9bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qvr969ois"/><path class="wuqa13gqk"/><path class="wsyyf2bqs"/><path class="qw_fs9bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jupyter" {...props}></Icon>
