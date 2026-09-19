<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs1so-b4l.css';
import '../../css/w/wobm3acef.css';
import '../../css/x/x5lbktbtf.css';
import '../../css/h/hzem-r0io.css';
import '../../css/v/vjbvj13aq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bs1so-b4l"/><circle class="wobm3acef"/><circle class="x5lbktbtf"/><circle class="hzem-r0io"/><path class="vjbvj13aq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:prompt-template" {...props}></Icon>
