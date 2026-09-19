<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa_146bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aa_146bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:qr-code" {...props}></Icon>
