<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3ndafbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3ndafbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:log-in-circle" {...props}></Icon>
