<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe5qejdtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":182,"height":218};
const content = `<path class="oe5qejdtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bitwarden" {...props}></Icon>
