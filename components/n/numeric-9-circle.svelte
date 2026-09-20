<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z58j8ibmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z58j8ibmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-9-circle" {...props}></Icon>
