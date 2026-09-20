<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgjah_2-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgjah_2-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:flask-line" {...props}></Icon>
