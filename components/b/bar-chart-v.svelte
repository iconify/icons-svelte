<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvd31abxp.css';
import '../../css/e/e-1c61b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nvd31abxp"/><path class="e-1c61b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:bar-chart-v" {...props}></Icon>
