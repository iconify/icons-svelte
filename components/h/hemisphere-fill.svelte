<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx9dn2b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx9dn2b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hemisphere-fill" {...props}></Icon>
