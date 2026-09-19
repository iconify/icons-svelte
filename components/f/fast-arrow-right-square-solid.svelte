<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwxmhvb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wwxmhvb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-right-square-solid" {...props}></Icon>
