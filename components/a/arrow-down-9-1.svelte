<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqfe31b7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="jqfe31b7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-9-1" {...props}></Icon>
