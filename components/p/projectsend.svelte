<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2uqve8ay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d2uqve8ay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:projectsend" {...props}></Icon>
