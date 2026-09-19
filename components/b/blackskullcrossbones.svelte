<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljkqsabqw.css';
import '../../css/k/k8gf3yb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljkqsabqw"/><path class="k8gf3yb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackskullcrossbones" {...props}></Icon>
