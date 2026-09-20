<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm28-rp8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm28-rp8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bugsnag" {...props}></Icon>
