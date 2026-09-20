<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jidwjib6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jidwjib6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:annoyed" {...props}></Icon>
