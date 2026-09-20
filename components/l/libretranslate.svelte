<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3s_f7bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3s_f7bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:libretranslate" {...props}></Icon>
