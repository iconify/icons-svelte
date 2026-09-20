<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgdcv4r6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgdcv4r6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-apps-add-widget" {...props}></Icon>
