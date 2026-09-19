<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo2e3-i0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="eo2e3-i0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-asterisk-filled" {...props}></Icon>
