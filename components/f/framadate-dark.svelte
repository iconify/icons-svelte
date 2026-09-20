<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1ozk6l8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a1ozk6l8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:framadate-dark" {...props}></Icon>
