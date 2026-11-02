<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob7vlsf5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob7vlsf5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:kite-fill" {...props}></Icon>
