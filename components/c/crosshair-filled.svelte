<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7s-3o5ea.css';
import '../../css/c/cd94oju7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7s-3o5ea"/><path clip-rule="evenodd" class="cd94oju7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:crosshair-filled" {...props}></Icon>
