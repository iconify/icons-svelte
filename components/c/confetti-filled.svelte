<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccbmiy8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iccbmiy8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:confetti-filled" {...props}></Icon>
