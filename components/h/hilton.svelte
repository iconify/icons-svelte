<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scfrf-bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scfrf-bbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hilton" {...props}></Icon>
