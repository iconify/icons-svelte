<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkvvucbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jkvvucbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:kick-16" {...props}></Icon>
