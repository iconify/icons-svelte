<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th42spb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="th42spb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-stairs" {...props}></Icon>
