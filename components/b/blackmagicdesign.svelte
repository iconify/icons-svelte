<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd01x7bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd01x7bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:blackmagicdesign" {...props}></Icon>
