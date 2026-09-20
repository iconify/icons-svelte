<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilnq8gpil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ilnq8gpil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:microsoft" {...props}></Icon>
