<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on-v0u84l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on-v0u84l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-tap-fill" {...props}></Icon>
