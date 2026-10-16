<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycclpjbnb.css';
import '../../css/n/ndahk2b0e.css';
import '../../css/n/nh3pp-bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ycclpjbnb"/><path class="ndahk2b0e"/><path class="nh3pp-bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:imbalance-48" {...props}></Icon>
