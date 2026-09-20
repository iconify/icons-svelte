<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn6e9-bly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kn6e9-bly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-plug" {...props}></Icon>
