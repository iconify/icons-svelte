<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6h7smbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v6h7smbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chart-3d" {...props}></Icon>
