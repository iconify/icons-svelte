<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l71al9aji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l71al9aji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-snowboarding" {...props}></Icon>
