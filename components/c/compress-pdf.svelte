<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwd061b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fwd061b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:compress-pdf" {...props}></Icon>
