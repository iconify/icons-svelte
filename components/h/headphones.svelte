<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw1q1ws-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw1q1ws-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:headphones" {...props}></Icon>
