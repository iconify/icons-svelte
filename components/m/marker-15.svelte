<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqkcty9kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="eqkcty9kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:marker-15" {...props}></Icon>
