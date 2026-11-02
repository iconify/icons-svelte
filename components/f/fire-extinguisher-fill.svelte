<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku7oxq-5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku7oxq-5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fire-extinguisher-fill" {...props}></Icon>
