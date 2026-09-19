<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/sbs8qrbjk.css';
import '../../css/z/zfv58jbiu.css';
import '../../css/j/jcz1l13ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sbs8qrbjk"/><path class="zfv58jbiu"/><path class="jcz1l13ji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:musical-score" {...props}></Icon>
