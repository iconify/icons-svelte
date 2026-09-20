<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evn57iodh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="evn57iodh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:car-repair" {...props}></Icon>
