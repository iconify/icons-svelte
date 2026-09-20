<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu0vt1yam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu0vt1yam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-top-right-main-light" {...props}></Icon>
