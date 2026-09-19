<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ub_o4lqpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ub_o4lqpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:alcohol" {...props}></Icon>
