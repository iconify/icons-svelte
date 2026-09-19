<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9-imr2-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9-imr2-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:award-fill" {...props}></Icon>
