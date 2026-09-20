<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov5bo0d0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ov5bo0d0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:emoji-joy-solid" {...props}></Icon>
