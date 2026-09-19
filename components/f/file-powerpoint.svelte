<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecs7db2qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ecs7db2qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:file-powerpoint" {...props}></Icon>
