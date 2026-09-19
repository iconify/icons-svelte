<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcbi4xmlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tcbi4xmlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:laptop" {...props}></Icon>
