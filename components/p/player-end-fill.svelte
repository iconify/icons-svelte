<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me8lomb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="me8lomb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-end-fill" {...props}></Icon>
