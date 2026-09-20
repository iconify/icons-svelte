<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g87xqnb5e.css';
import '../../css/x/x2qi6i_is.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/l/lak7h71xg.css';
import '../../css/m/mr0ernben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="g87xqnb5e"/><path class="x2qi6i_is"/><g class="jn8qy4bru"><path class="lak7h71xg"/><circle class="mr0ernben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:male-sign" {...props}></Icon>
