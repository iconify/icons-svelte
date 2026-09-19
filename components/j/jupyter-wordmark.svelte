<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsgr4acwq.css';
import '../../css/q/qvr969ois.css';
import '../../css/w/wuqa13gqk.css';
import '../../css/j/j171pzbgu.css';
import '../../css/h/ha5b2dbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qsgr4acwq"/><path class="qvr969ois"/><path class="wuqa13gqk"/><path class="j171pzbgu"/><path class="ha5b2dbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jupyter-wordmark" {...props}></Icon>
