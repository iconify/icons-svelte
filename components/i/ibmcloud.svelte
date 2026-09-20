<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6lc-5iso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6lc-5iso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ibmcloud" {...props}></Icon>
