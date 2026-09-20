<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tny4sibjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tny4sibjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-computer" {...props}></Icon>
