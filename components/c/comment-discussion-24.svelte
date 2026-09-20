<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgfmt1b6e.css';
import '../../css/y/yo3cu2bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgfmt1b6e"/><path class="yo3cu2bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-discussion-24" {...props}></Icon>
