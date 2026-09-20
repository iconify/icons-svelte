<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhxy26blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nhxy26blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bulb-off-solid" {...props}></Icon>
