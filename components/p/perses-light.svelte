<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iivb983tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iivb983tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:perses-light" {...props}></Icon>
