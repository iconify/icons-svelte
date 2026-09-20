<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xym44vlld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xym44vlld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:get-pocket" {...props}></Icon>
