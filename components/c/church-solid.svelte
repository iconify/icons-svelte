<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7lr2mkyr.css';
import '../../css/h/hhhhlk_ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j7lr2mkyr"/><path class="hhhhlk_ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:church-solid" {...props}></Icon>
