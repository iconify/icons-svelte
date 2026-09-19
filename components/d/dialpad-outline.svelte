<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6ptfys8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6ptfys8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dialpad-outline" {...props}></Icon>
