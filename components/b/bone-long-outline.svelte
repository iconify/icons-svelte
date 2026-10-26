<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-bp_jbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o-bp_jbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:bone-long-outline" {...props}></Icon>
