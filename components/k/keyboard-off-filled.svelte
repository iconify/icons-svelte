<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd8xp2a-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zd8xp2a-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:keyboard-off-filled" {...props}></Icon>
