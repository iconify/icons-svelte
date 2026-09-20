<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbf_gokak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbf_gokak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:cube" {...props}></Icon>
