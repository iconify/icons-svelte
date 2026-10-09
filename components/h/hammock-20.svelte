<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubixxqbpx.css';
import '../../css/r/rum39npnf.css';
import '../../css/c/cfji69bfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubixxqbpx"/><path class="rum39npnf"/><path class="cfji69bfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammock-20" {...props}></Icon>
