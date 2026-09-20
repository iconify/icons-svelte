<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra4arbcap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4arbcap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flag-chequered-sharp" {...props}></Icon>
