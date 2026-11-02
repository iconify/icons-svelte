<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zog-z0bzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zog-z0bzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magic-2-fill" {...props}></Icon>
