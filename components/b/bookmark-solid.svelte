<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd8rxbb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bd8rxbb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:bookmark-solid" {...props}></Icon>
