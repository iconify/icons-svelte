<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgz6urfor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qgz6urfor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:radar" {...props}></Icon>
