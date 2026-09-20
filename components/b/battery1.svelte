<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvhx7ob_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vvhx7ob_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:battery1" {...props}></Icon>
