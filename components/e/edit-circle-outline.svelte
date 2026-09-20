<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prjatmbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="prjatmbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:edit-circle-outline" {...props}></Icon>
