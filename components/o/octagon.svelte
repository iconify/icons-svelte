<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na_uq7bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="na_uq7bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:octagon" {...props}></Icon>
