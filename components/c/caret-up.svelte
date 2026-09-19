<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arv9ch36c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="arv9ch36c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-up" {...props}></Icon>
