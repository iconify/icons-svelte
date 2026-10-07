<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u06_j4b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u06_j4b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pen-connect-bluetooth" {...props}></Icon>
