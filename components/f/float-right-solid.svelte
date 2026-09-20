<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og380tjvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="og380tjvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:float-right-solid" {...props}></Icon>
