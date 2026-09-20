<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2p0nnb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2p0nnb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:list-unordered-24" {...props}></Icon>
