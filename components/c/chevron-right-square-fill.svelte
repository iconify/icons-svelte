<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxb0617gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fxb0617gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-right-square-fill" {...props}></Icon>
