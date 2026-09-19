<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk2po9bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zk2po9bxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file" {...props}></Icon>
