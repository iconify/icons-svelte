<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0fdabcsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0fdabcsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-commit-line" {...props}></Icon>
