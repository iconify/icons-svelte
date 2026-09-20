<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeuiky0sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeuiky0sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-diagonal-2" {...props}></Icon>
