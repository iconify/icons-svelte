<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzr84ybok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzr84ybok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:grid" {...props}></Icon>
