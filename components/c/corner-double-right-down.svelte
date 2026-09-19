<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlcle3b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlcle3b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:corner-double-right-down" {...props}></Icon>
