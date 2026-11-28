<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7a_yubni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7a_yubni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:radiation" {...props}></Icon>
