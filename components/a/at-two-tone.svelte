<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il93k7bjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="il93k7bjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:at-two-tone" {...props}></Icon>
