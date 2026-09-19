<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozm9twbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ozm9twbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:meteor" {...props}></Icon>
