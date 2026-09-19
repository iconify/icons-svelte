<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo4ywkbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yo4ywkbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hexadite-investigation-semi-auto" {...props}></Icon>
