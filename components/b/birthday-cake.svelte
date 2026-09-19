<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew1hd7bhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ew1hd7bhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:birthday-cake" {...props}></Icon>
