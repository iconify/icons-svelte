<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5c9j5b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5c9j5b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-2-fill" {...props}></Icon>
