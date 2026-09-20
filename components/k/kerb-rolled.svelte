<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgjx29b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zgjx29b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:kerb-rolled" {...props}></Icon>
