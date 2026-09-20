<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j24t_zsqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="j24t_zsqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:facebook" {...props}></Icon>
