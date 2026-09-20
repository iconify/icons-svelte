<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5t5jabpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="t5t5jabpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:genie" {...props}></Icon>
