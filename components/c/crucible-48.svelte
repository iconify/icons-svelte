<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te48i79xt.css';
import '../../css/s/syysw3b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="te48i79xt"/><path class="syysw3b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crucible-48" {...props}></Icon>
