<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb32mdgiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb32mdgiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:chevron-right-line" {...props}></Icon>
