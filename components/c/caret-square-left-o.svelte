<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cflr1ab0i.css';
import '../../css/u/uxoqws25i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cflr1ab0i"/><path class="uxoqws25i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:caret-square-left-o" {...props}></Icon>
