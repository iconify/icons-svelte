<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjudv46oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sjudv46oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:direction-adjustment-three" {...props}></Icon>
