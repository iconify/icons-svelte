<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzswmf6nk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qzswmf6nk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:focus-points" {...props}></Icon>
