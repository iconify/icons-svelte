<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auvv4vosw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="auvv4vosw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-equipment-film-print" {...props}></Icon>
