<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqeckf5cb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eqeckf5cb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:files-pinwheel" {...props}></Icon>
