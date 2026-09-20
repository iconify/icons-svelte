<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw64edj9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw64edj9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-down" {...props}></Icon>
