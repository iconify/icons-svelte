<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsr4tr44z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bsr4tr44z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-repeat-list-fill" {...props}></Icon>
