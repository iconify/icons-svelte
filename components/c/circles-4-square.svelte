<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhwo19b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uhwo19b5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circles-4-square" {...props}></Icon>
