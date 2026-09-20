<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrem-nbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrem-nbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pump" {...props}></Icon>
