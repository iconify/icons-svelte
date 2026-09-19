<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhzrw9b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhzrw9b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:livescript" {...props}></Icon>
