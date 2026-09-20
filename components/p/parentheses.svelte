<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-2te59_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-2te59_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:parentheses" {...props}></Icon>
