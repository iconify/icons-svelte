<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okjox9bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="okjox9bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eraser-16" {...props}></Icon>
