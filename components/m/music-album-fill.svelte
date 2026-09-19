<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa2qbuzpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa2qbuzpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-album-fill" {...props}></Icon>
