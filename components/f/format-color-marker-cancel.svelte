<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g973wvayq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g973wvayq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-color-marker-cancel" {...props}></Icon>
