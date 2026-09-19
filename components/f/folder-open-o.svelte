<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5-ql04qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1408};
const content = `<path class="h5-ql04qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:folder-open-o" {...props}></Icon>
