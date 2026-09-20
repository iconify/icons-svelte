<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpffbdjyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cpffbdjyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-diagonal-2-solid" {...props}></Icon>
