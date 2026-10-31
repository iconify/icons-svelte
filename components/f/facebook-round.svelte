<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwbo4nbbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwbo4nbbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:facebook-round" {...props}></Icon>
