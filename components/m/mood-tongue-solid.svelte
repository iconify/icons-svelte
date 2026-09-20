<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfvpij5gy.css';
import '../../css/j/jdy0pvxyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dfvpij5gy"/><path clip-rule="evenodd" class="jdy0pvxyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-tongue-solid" {...props}></Icon>
