<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqch9n6xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqch9n6xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:folder-3" {...props}></Icon>
