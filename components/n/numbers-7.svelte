<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v29dpw61b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v29dpw61b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-7" {...props}></Icon>
