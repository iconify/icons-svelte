<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pshkky4_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pshkky4_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-2-line" {...props}></Icon>
