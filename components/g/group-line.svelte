<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8xbe_bhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v8xbe_bhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:group-line" {...props}></Icon>
