<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpd2i7b0i.css';
import '../../css/t/th-zvacct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vpd2i7b0i"/><path class="th-zvacct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:hashicorp" {...props}></Icon>
