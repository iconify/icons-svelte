<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umfp6gevz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="umfp6gevz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flame-sharp-duotone" {...props}></Icon>
