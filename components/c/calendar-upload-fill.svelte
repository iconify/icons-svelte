<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-_gzdw1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-_gzdw1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:calendar-upload-fill" {...props}></Icon>
