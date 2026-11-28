<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iliajm18t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iliajm18t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:align-right" {...props}></Icon>
