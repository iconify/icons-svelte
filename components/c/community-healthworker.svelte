<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js7zi3nwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="js7zi3nwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:community-healthworker" {...props}></Icon>
