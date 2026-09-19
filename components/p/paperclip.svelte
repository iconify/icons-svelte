<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b603scljm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b603scljm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:paperclip" {...props}></Icon>
