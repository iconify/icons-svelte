<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqhrbpoig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqhrbpoig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:location" {...props}></Icon>
