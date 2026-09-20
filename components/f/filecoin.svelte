<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjp1dex-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjp1dex-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:filecoin" {...props}></Icon>
