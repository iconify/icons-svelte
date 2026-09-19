<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugrbgq96k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugrbgq96k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackdownpointingbackhand" {...props}></Icon>
