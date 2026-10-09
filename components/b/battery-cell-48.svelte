<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d88tubblx.css';
import '../../css/a/a3i1g1emt.css';
import '../../css/q/qayriggpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d88tubblx"/><path class="a3i1g1emt"/><path class="qayriggpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-cell-48" {...props}></Icon>
