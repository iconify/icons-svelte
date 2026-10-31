<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwpl20c6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwpl20c6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:power-gloss" {...props}></Icon>
