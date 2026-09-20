<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3d6jyb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y3d6jyb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:printables-dark" {...props}></Icon>
