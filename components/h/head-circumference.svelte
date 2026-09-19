<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd4wc4bhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qd4wc4bhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:head-circumference" {...props}></Icon>
