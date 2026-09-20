<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4545e9po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a4545e9po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bulb-on-solid" {...props}></Icon>
