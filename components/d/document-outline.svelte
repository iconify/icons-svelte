<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9cp-0g3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9cp-0g3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:document-outline" {...props}></Icon>
