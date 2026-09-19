<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlgp2b63v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mlgp2b63v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:clipboard" {...props}></Icon>
