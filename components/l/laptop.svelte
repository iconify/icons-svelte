<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htm0r7sqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htm0r7sqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:laptop" {...props}></Icon>
