<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrwijsb_g.css';
import '../../css/t/t2wyy31bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vrwijsb_g"/><path class="t2wyy31bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:furniture-15" {...props}></Icon>
