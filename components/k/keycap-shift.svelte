<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa0wtpyvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xa0wtpyvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-shift" {...props}></Icon>
