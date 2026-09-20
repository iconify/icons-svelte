<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9j15gb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9j15gb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codeforces" {...props}></Icon>
