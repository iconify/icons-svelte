<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl93aw29w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl93aw29w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hivemq" {...props}></Icon>
