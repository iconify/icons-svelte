<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox7ar-sbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox7ar-sbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:elavon" {...props}></Icon>
