<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge8cev9ng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ge8cev9ng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:face-rolling-eyes" {...props}></Icon>
