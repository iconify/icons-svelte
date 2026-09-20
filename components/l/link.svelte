<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2m7awbvd.css';
import '../../css/g/ggfvuibun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b2m7awbvd"/><path class="ggfvuibun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:link" {...props}></Icon>
