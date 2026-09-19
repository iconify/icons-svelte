<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gev1hsbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gev1hsbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:buzzfeed" {...props}></Icon>
