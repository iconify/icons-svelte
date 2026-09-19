<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssm45ytaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ssm45ytaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half" {...props}></Icon>
