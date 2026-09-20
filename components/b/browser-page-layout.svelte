<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hss8mqb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hss8mqb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:browser-page-layout" {...props}></Icon>
