<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqp835bas.css';
import '../../css/z/zz538uboq.css';
import '../../css/a/a_rdqgb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rqp835bas"/><path class="zz538uboq"/><path class="a_rdqgb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:kite-20-bold" {...props}></Icon>
