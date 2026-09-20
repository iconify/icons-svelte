<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyv0qi4vm.css';
import '../../css/r/r62u3xcnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pyv0qi4vm"/><path class="r62u3xcnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gauge-low-16" {...props}></Icon>
