<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyvy4ik0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kyvy4ik0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:magnet-16" {...props}></Icon>
