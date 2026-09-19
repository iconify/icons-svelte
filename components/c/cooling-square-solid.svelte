<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqo9-i3ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqo9-i3ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:cooling-square-solid" {...props}></Icon>
