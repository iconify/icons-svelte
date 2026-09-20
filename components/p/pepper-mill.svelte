<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-ec6nb8h.css';
import '../../css/d/dtlzvx9dw.css';
import '../../css/o/o8myxnbyd.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/z/zvlp41bor.css';
import '../../css/e/el7kd0g5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="q-ec6nb8h"/><path class="dtlzvx9dw"/><path class="o8myxnbyd"/><g class="jn8qy4bru"><path class="zvlp41bor"/><path class="el7kd0g5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pepper-mill" {...props}></Icon>
