<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-mgfz0ds.css';
import '../../css/m/m-lu0swiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="b-mgfz0ds"/><path class="m-lu0swiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:dress" {...props}></Icon>
