<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkozawy4w.css';
import '../../css/b/b0mwi-brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkozawy4w"/><path clip-rule="evenodd" class="b0mwi-brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifier-check-outline" {...props}></Icon>
