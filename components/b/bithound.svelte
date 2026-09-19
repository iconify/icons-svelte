<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz66qlb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":466,"height":512};
const content = `<path class="pz66qlb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bithound" {...props}></Icon>
