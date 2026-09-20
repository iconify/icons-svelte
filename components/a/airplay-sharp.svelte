<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yi0c9ccqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yi0c9ccqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airplay-sharp" {...props}></Icon>
