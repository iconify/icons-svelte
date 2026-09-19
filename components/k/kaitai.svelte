<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeh4fhb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zeh4fhb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:kaitai" {...props}></Icon>
