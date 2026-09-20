<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcivgub7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bcivgub7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cursor-filled" {...props}></Icon>
