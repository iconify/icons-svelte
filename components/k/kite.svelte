<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez53olodr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ez53olodr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:kite" {...props}></Icon>
