<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asrsfxb5s.css';
import '../../css/m/mepmou5ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="asrsfxb5s"/><path class="mepmou5ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pizza" {...props}></Icon>
