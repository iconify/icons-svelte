<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9ji8acvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9ji8acvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-solid" {...props}></Icon>
