<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i20v4--ys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i20v4--ys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:customink" {...props}></Icon>
