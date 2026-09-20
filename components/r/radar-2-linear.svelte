<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr28umbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr28umbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:radar-2-linear" {...props}></Icon>
