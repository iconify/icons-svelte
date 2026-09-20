<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw6mbk9pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw6mbk9pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-round-sharp" {...props}></Icon>
