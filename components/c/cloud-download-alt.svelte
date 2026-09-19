<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ods3bac7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ods3bac7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cloud-download-alt" {...props}></Icon>
