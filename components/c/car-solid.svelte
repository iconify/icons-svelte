<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br4kg7krz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="br4kg7krz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:car-solid" {...props}></Icon>
