<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sprj5mb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="sprj5mb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-download-add" {...props}></Icon>
