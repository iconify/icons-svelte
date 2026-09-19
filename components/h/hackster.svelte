<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v08s5_dtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v08s5_dtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:hackster" {...props}></Icon>
