<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-amm-_uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l-amm-_uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-surprise" {...props}></Icon>
