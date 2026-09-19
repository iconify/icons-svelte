<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amlj5scla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amlj5scla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nessus" {...props}></Icon>
