<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8zq3bce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8zq3bce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-line" {...props}></Icon>
