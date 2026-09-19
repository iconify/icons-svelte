<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfn9sqbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="kfn9sqbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:male" {...props}></Icon>
