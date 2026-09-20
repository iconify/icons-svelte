<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na7hrpbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="na7hrpbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:arrow-up-4-solid" {...props}></Icon>
