<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyci3rbny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":109,"height":87};
const content = `<path class="vyci3rbny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gozle" {...props}></Icon>
