<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv19rdkrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv19rdkrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pkgsrc" {...props}></Icon>
