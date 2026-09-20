<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_2ax6o9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_2ax6o9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:comment-24" {...props}></Icon>
