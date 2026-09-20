<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9bnolcdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9bnolcdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkbox-marked-circle-outline" {...props}></Icon>
