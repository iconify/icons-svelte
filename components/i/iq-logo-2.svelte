<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1nfedbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1nfedbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iq-logo-2" {...props}></Icon>
