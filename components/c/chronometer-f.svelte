<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_stj679q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="x_stj679q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chronometer-f" {...props}></Icon>
