<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thembzy5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="thembzy5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nintendo64" {...props}></Icon>
