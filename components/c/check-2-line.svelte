<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh040mbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh040mbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:check-2-line" {...props}></Icon>
