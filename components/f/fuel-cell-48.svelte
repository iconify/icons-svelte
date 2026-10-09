<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_hcd3bgg.css';
import '../../css/q/qi6qfqz0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j_hcd3bgg"/><path class="qi6qfqz0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-cell-48" {...props}></Icon>
