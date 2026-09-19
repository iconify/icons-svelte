<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rym86fbok.css';
import '../../css/n/ni4bbebcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rym86fbok"/><path class="ni4bbebcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:modified-date-outlined" {...props}></Icon>
