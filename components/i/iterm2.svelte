<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b22rc5bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b22rc5bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:iterm2" {...props}></Icon>
