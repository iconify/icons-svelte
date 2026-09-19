<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkud4olzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mkud4olzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:commitizen" {...props}></Icon>
