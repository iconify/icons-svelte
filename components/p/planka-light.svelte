<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y245uab7e.css';
import '../../css/z/ziuppeksn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y245uab7e"/><path class="ziuppeksn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planka-light" {...props}></Icon>
