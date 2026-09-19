<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjrwn3y5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yjrwn3y5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-circle-minus" {...props}></Icon>
