<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1-a7t4hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v1-a7t4hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-panel-off" {...props}></Icon>
