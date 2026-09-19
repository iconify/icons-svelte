<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy251cc0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dy251cc0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-up-circle-solid" {...props}></Icon>
