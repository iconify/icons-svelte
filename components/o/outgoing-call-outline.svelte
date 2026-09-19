<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqqcwzbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqqcwzbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:outgoing-call-outline" {...props}></Icon>
