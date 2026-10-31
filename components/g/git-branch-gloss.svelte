<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl26vvbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nl26vvbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-branch-gloss" {...props}></Icon>
