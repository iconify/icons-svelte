<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syhi_kb3g.css';
import '../../css/n/n47jdbbqa.css';
import '../../css/p/py966wb9m.css';
import '../../css/l/lyb69fbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="syhi_kb3g"/><path class="n47jdbbqa"/><path class="py966wb9m"/><path class="lyb69fbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:paintbrush" {...props}></Icon>
