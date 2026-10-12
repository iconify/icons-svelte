<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_ktldbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="za_ktldbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-square-48-bold" {...props}></Icon>
