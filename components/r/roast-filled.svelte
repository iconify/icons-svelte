<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w91-9k59o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w91-9k59o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:roast-filled" {...props}></Icon>
