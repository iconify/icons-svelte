<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inyh17byw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inyh17byw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fire-filled" {...props}></Icon>
