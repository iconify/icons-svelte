<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa7_ribhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa7_ribhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:pause" {...props}></Icon>
