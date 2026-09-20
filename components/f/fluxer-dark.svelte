<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esoknpbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="esoknpbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluxer-dark" {...props}></Icon>
