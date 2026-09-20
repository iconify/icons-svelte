<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7hydcubz.css';
import '../../css/y/y65flgbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="g7hydcubz"/><path class="y65flgbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:remove-1d" {...props}></Icon>
