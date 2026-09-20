<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2yj7pbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2yj7pbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bing" {...props}></Icon>
