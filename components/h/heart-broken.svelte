<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax92y6w3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax92y6w3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heart-broken" {...props}></Icon>
