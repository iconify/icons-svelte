<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5e20cb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e20cb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-left" {...props}></Icon>
