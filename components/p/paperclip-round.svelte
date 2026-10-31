<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihk9poypq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihk9poypq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paperclip-round" {...props}></Icon>
