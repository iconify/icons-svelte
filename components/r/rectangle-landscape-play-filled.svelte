<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uri4frb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uri4frb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-landscape-play-filled" {...props}></Icon>
