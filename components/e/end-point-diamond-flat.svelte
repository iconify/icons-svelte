<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7azlbut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hn7azlbut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:end-point-diamond-flat" {...props}></Icon>
