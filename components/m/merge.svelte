<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6-y9-87l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l6-y9-87l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:merge" {...props}></Icon>
