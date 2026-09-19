<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixxthgb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ixxthgb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-seven" {...props}></Icon>
