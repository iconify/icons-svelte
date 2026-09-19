<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqn04vbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eqn04vbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:diamond-two" {...props}></Icon>
