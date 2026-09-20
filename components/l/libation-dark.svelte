<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk1khyh6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hk1khyh6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:libation-dark" {...props}></Icon>
