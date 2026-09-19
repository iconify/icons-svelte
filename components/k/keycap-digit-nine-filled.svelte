<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8bdu7buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l8bdu7buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-nine-filled" {...props}></Icon>
