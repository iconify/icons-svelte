<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o16vbibxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":192,"height":512};
const content = `<path class="o16vbibxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:ellipsis-v" {...props}></Icon>
