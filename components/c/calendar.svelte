<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3ti-bn3p.css';
import '../../css/g/gjagohdeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="i3ti-bn3p"/><path class="gjagohdeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:calendar" {...props}></Icon>
