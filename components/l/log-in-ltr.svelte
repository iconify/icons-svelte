<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh-fv613y.css';
import '../../css/l/leg-f-qxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kh-fv613y"/><path class="leg-f-qxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:log-in-ltr" {...props}></Icon>
