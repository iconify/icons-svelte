<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlv2fmbfj.css';
import '../../css/u/u1l779tda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlv2fmbfj"/><path class="u1l779tda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pomerium" {...props}></Icon>
