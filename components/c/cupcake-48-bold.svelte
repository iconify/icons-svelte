<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc4hu_b3q.css';
import '../../css/k/kigjocbeh.css';
import '../../css/j/jqo23tbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oc4hu_b3q"/><path class="kigjocbeh"/><path class="jqo23tbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cupcake-48-bold" {...props}></Icon>
