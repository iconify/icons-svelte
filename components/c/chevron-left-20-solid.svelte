<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb7zqp66w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jb7zqp66w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-left-20-solid" {...props}></Icon>
