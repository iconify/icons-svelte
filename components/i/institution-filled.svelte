<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi7qo4bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi7qo4bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:institution-filled" {...props}></Icon>
