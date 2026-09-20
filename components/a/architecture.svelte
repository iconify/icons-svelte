<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co_in-c0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co_in-c0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:architecture" {...props}></Icon>
