<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/had4r1bdj.css';
import '../../css/w/wjz6iob6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="had4r1bdj"/><path class="wjz6iob6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:inbox-stack-16-solid" {...props}></Icon>
