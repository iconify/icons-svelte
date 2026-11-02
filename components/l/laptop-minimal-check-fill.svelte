<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2j6t6bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2j6t6bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laptop-minimal-check-fill" {...props}></Icon>
