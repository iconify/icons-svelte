<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emhpwub6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="emhpwub6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-down-12" {...props}></Icon>
