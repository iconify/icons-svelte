<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1y2cwd5s.css';
import '../../css/x/xxvlnybzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k1y2cwd5s"/><path class="xxvlnybzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:battery-4-solid" {...props}></Icon>
