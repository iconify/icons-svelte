<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bul0zbb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bul0zbb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database-setting-solid" {...props}></Icon>
