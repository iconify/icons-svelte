<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb71phbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wb71phbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:blood-types-1-bold" {...props}></Icon>
