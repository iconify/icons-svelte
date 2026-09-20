<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pylves6hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pylves6hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-feedly" {...props}></Icon>
