<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuuoc0zvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuuoc0zvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:api" {...props}></Icon>
