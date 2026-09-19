<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xys7sp8ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xys7sp8ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-skull" {...props}></Icon>
