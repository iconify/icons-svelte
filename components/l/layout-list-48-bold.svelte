<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iht0nqksq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iht0nqksq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:layout-list-48-bold" {...props}></Icon>
