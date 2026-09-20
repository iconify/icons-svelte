<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4-404nwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4-404nwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:content-save-all-outline" {...props}></Icon>
