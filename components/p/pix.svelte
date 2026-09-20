<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy-uluafk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fy-uluafk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pix" {...props}></Icon>
