<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0o86vbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i0o86vbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:playstation" {...props}></Icon>
