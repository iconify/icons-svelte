<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m52xe297f.css';
import '../../css/q/qdp4kbckc.css';
import '../../css/y/y3mtozbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m52xe297f"/><path class="qdp4kbckc"/><path class="y3mtozbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:plane" {...props}></Icon>
