<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxpc9z8vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxpc9z8vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-window-cursor-fill" {...props}></Icon>
