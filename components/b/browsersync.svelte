<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn4aefjsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":360,"height":512};
const content = `<path class="tn4aefjsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:browsersync" {...props}></Icon>
