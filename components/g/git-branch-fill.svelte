<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8djc38rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8djc38rd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-fill" {...props}></Icon>
