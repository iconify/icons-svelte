<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4lpbh9cz.css';
import '../../css/j/jb-34lb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4lpbh9cz"/><path class="jb-34lb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:houses-1-filled" {...props}></Icon>
