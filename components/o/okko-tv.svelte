<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evkb4nhxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evkb4nhxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:okko-tv" {...props}></Icon>
