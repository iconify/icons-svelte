<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qby9oorro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qby9oorro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag3-filled" {...props}></Icon>
