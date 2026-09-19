<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isioz2bhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="isioz2bhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blackquestionmark" {...props}></Icon>
