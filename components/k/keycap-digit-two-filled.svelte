<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk3hwbdsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kk3hwbdsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-two-filled" {...props}></Icon>
