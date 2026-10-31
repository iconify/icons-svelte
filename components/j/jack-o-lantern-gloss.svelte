<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt9rf2bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt9rf2bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:jack-o-lantern-gloss" {...props}></Icon>
