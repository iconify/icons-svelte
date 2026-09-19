<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de16aetek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de16aetek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:devices" {...props}></Icon>
