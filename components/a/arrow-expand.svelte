<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i668ksbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i668ksbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-expand" {...props}></Icon>
