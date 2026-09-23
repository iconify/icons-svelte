<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-up1856y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-up1856y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:command-sharp-duotone" {...props}></Icon>
