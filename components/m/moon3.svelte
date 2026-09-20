<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu06ygb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu06ygb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:moon3" {...props}></Icon>
