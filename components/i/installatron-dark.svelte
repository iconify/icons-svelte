<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eua6ogqea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eua6ogqea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:installatron-dark" {...props}></Icon>
