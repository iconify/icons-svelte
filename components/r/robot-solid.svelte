<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miclccyag.css';
import '../../css/x/x_a_cwb1g.css';
import '../../css/z/zdyze6bia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="miclccyag"/><path clip-rule="evenodd" class="x_a_cwb1g"/><path class="zdyze6bia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:robot-solid" {...props}></Icon>
