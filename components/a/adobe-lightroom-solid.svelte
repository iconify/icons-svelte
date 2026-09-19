<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5q30_6zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5q30_6zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-lightroom-solid" {...props}></Icon>
