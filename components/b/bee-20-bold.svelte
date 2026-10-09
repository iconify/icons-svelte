<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esurz2baj.css';
import '../../css/o/o42t0kkwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="esurz2baj"/><path class="o42t0kkwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bee-20-bold" {...props}></Icon>
