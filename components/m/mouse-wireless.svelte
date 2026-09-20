<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohkgcchcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ohkgcchcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mouse-wireless" {...props}></Icon>
