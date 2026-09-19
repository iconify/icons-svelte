<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrojon6us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1025};
const content = `<path class="hrojon6us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:crayon" {...props}></Icon>
