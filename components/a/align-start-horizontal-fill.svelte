<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnz9l5-su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnz9l5-su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-start-horizontal-fill" {...props}></Icon>
