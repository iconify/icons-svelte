<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvkwmin5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvkwmin5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cash-fill" {...props}></Icon>
