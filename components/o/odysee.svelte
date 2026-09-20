<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgiol0bhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgiol0bhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:odysee" {...props}></Icon>
