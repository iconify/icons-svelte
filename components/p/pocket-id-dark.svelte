<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be0atlklu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="be0atlklu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-id-dark" {...props}></Icon>
