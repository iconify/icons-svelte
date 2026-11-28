<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy9y9-beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy9y9-beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bridge" {...props}></Icon>
