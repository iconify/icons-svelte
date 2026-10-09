<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlsrljbwz.css';
import '../../css/t/t2_6nubta.css';
import '../../css/t/t92t96xsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rlsrljbwz"/><path class="t2_6nubta"/><path class="t92t96xsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:esg-48" {...props}></Icon>
