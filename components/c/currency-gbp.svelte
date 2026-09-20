<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgff4ownd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgff4ownd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:currency-gbp" {...props}></Icon>
