<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh775pm9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vh775pm9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gotosocial-dark" {...props}></Icon>
