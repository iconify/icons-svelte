<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jndqku9wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jndqku9wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:renovate" {...props}></Icon>
