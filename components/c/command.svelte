<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3-_ddc6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g3-_ddc6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:command" {...props}></Icon>
