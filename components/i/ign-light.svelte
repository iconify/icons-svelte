<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c092uo0hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c092uo0hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ign-light" {...props}></Icon>
