<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7asodbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7asodbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:govee-h6076" {...props}></Icon>
