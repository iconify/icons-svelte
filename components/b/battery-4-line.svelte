<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbgz55b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbgz55b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-4-line" {...props}></Icon>
