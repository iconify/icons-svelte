<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2cp8swzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2cp8swzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:app-window-mac-minus" {...props}></Icon>
