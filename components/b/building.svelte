<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvkp7fb-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvkp7fb-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:building" {...props}></Icon>
