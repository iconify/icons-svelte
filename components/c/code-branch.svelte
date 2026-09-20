<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehb82bc3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehb82bc3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:code-branch" {...props}></Icon>
