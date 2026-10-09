<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6julkbke.css';
import '../../css/t/t5m9mnbka.css';
import '../../css/x/x67cv140v.css';
import '../../css/x/xwei6nojw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t6julkbke"/><path class="t5m9mnbka"/><path class="x67cv140v"/><path class="xwei6nojw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rooftop-wind-20" {...props}></Icon>
