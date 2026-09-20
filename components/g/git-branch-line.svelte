<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihvzegruc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihvzegruc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-line" {...props}></Icon>
