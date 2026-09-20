<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oumarsd0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oumarsd0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-flare" {...props}></Icon>
