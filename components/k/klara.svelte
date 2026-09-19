<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3ahqyuwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ahqyuwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:klara" {...props}></Icon>
