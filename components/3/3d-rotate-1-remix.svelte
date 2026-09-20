<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iitqzl8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iitqzl8zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:3d-rotate-1-remix" {...props}></Icon>
