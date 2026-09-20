<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnw89d4it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rnw89d4it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-diagonal-2" {...props}></Icon>
