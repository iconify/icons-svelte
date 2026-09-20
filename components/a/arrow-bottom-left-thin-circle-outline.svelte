<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzw8d4ipa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzw8d4ipa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-left-thin-circle-outline" {...props}></Icon>
