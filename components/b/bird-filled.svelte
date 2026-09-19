<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdwq5tblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qdwq5tblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bird-filled" {...props}></Icon>
