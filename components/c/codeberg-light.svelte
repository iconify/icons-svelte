<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fujqedbkp.css';
import '../../css/e/e15e1_l3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fujqedbkp"/><path class="e15e1_l3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codeberg-light" {...props}></Icon>
