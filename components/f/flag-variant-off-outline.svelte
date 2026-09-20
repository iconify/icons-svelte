<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqusocckw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqusocckw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flag-variant-off-outline" {...props}></Icon>
