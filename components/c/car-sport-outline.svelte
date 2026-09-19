<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7_fn5bzo.css';
import '../../css/g/g7v3m3bhf.css';
import '../../css/e/eu_shmbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c7_fn5bzo"/><path class="g7v3m3bhf"/><path class="eu_shmbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:car-sport-outline" {...props}></Icon>
