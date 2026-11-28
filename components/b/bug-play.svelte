<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umax9m-3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umax9m-3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bug-play" {...props}></Icon>
