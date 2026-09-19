<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk7j9cb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rk7j9cb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:console-filled" {...props}></Icon>
