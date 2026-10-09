<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqjbftbwq.css';
import '../../css/q/qi4gmjz3h.css';
import '../../css/h/hjy7c8brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kqjbftbwq"/><path class="qi4gmjz3h"/><path class="hjy7c8brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hotel-48" {...props}></Icon>
