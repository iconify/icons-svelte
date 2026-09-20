<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl7tifc-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl7tifc-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flower-sharp-fill" {...props}></Icon>
