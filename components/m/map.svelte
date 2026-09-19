<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntlcj1e_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntlcj1e_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:map" {...props}></Icon>
