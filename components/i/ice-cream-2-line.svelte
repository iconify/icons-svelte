<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvdb1sbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvdb1sbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ice-cream-2-line" {...props}></Icon>
