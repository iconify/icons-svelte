<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky1333a9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky1333a9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:milk-filled" {...props}></Icon>
