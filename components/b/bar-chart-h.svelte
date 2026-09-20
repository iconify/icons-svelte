<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvd31abxp.css';
import '../../css/w/wvhlhkrav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="wvhlhkrav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bar-chart-h" {...props}></Icon>
