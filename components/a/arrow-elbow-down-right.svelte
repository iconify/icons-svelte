<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1h05m76n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1h05m76n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-elbow-down-right" {...props}></Icon>
