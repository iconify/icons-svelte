<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fthgilgrb.css';
import '../../css/y/yhd0eaczw.css';
import '../../css/z/z8wtxdbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fthgilgrb"/><path class="yhd0eaczw"/><path class="z8wtxdbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kamiyomu-dark" {...props}></Icon>
