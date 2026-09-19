<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hncin7bkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hncin7bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:buffer" {...props}></Icon>
