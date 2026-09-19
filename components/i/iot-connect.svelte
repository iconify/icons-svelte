<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gac48jb7z.css';
import '../../css/b/butntgbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gac48jb7z"/><path class="butntgbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:iot-connect" {...props}></Icon>
