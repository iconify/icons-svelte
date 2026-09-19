<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji7qdwgys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ji7qdwgys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:disabled-outline" {...props}></Icon>
