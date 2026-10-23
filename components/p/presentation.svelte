<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw55fhbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw55fhbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:presentation" {...props}></Icon>
