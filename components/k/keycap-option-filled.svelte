<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9l8h93fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m9l8h93fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-option-filled" {...props}></Icon>
