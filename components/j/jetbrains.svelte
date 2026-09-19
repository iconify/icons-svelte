<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwk5x-bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jwk5x-bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:jetbrains" {...props}></Icon>
