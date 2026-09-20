<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tew07ubqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tew07ubqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conslee-light" {...props}></Icon>
