<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6x1ojbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6x1ojbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-meh-blank" {...props}></Icon>
