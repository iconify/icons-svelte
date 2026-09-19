<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdudxp5df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="tdudxp5df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:linode" {...props}></Icon>
