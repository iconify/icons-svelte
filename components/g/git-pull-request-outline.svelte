<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_zincina.css';
import '../../css/h/h1ltq8ifw.css';
import '../../css/g/g9gmjl-2d.css';
import '../../css/a/aja_aog3q.css';
import '../../css/s/spy7zkbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q_zincina"/><path class="h1ltq8ifw"/><circle class="g9gmjl-2d"/><circle class="aja_aog3q"/><path class="spy7zkbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-pull-request-outline" {...props}></Icon>
