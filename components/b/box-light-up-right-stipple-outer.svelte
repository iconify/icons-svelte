<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmiclo8zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qmiclo8zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-right-stipple-outer" {...props}></Icon>
