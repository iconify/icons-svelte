<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gofesi5fa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gofesi5fa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:play" {...props}></Icon>
