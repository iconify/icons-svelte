<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbhfztbdk.css';
import '../../css/s/s3cdewurv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rbhfztbdk"/><path class="s3cdewurv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:excavator-48" {...props}></Icon>
