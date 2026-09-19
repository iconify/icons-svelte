<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mph4c5b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mph4c5b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-import" {...props}></Icon>
