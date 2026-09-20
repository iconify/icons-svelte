<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4bm79ayo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4bm79ayo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ampersand-solid" {...props}></Icon>
