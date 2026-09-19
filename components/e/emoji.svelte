<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_eu7vqxz.css';
import '../../css/l/l-ctnfbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_eu7vqxz"/><path class="l-ctnfbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:emoji" {...props}></Icon>
