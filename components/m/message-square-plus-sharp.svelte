<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd6xuok-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd6xuok-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-plus-sharp" {...props}></Icon>
