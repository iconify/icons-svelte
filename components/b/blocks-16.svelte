<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2os41gof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t2os41gof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:blocks-16" {...props}></Icon>
