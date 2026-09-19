<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usud5lbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="usud5lbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-density-default" {...props}></Icon>
