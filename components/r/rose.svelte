<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ora3me5pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ora3me5pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:rose" {...props}></Icon>
