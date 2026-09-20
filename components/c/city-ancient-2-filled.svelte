<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4geurb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4geurb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-ancient-2-filled" {...props}></Icon>
