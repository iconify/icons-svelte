<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyfj73g9f.css';
import '../../css/v/vkc1wcb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyfj73g9f"/><path class="vkc1wcb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:infinigence" {...props}></Icon>
