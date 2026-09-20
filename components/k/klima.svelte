<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odmh5oz-e.css';
import '../../css/x/x0w8p7-8h.css';
import '../../css/k/kpkdmqbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="odmh5oz-e"/><path class="x0w8p7-8h"/><path class="kpkdmqbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:klima" {...props}></Icon>
