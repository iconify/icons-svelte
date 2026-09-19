<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot3ue-bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":512};
const content = `<path class="ot3ue-bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:cubit" {...props}></Icon>
