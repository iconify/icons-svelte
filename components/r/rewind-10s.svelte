<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncx9_cchy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncx9_cchy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:rewind-10s" {...props}></Icon>
