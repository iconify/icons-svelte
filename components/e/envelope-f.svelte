<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad72w3bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="ad72w3bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:envelope-f" {...props}></Icon>
