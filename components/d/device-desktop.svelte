<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7u4yomqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m7u4yomqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-desktop" {...props}></Icon>
