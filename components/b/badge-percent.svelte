<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh827rbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh827rbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:badge-percent" {...props}></Icon>
