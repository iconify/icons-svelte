<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-06c7hcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-06c7hcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-chevron-right-fill" {...props}></Icon>
