<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmg3ne9zk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hmg3ne9zk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:new-file" {...props}></Icon>
