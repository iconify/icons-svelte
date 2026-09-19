<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqg26ys5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg26ys5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:integral-filled" {...props}></Icon>
