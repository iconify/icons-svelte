<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9n4virpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9n4virpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:numbered-list-right" {...props}></Icon>
