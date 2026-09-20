<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3mqsdxzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="k3mqsdxzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:chart-style1" {...props}></Icon>
