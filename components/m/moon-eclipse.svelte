<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhhiimchi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhhiimchi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:moon-eclipse" {...props}></Icon>
