<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhfns4f4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhfns4f4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:eraser-solid" {...props}></Icon>
