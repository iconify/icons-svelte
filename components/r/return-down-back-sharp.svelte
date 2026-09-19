<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0jdfibba.css';
import '../../css/o/oidh77b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e0jdfibba"/><path class="oidh77b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:return-down-back-sharp" {...props}></Icon>
