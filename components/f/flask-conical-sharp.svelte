<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgv6vubxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgv6vubxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flask-conical-sharp" {...props}></Icon>
