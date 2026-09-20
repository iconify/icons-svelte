<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz2jks-da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vz2jks-da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:check-tick-16" {...props}></Icon>
