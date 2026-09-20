<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdfrg5bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xdfrg5bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:hand-grab" {...props}></Icon>
