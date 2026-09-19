<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znzw_sapr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="znzw_sapr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:phplist" {...props}></Icon>
