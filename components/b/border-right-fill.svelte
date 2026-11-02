<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpc6m9n0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gpc6m9n0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:border-right-fill" {...props}></Icon>
