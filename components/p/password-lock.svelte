<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxkm2urco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kxkm2urco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:password-lock" {...props}></Icon>
