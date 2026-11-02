<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfm0fpb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfm0fpb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-line" {...props}></Icon>
