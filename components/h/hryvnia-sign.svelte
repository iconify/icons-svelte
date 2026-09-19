<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-e__fb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o-e__fb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hryvnia-sign" {...props}></Icon>
