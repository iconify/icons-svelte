<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxelqf_ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxelqf_ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:email-attachment-image-remix" {...props}></Icon>
