<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv8o2ibxb.css';
import '../../css/q/qkmfhjfvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qv8o2ibxb"/><path class="qkmfhjfvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:file-process" {...props}></Icon>
