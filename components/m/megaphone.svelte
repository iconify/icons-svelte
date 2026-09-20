<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njrx_1w3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njrx_1w3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:megaphone" {...props}></Icon>
