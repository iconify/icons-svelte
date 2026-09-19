<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br6gkkbnm.css';
import '../../css/y/y8r8-nbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="br6gkkbnm"/><path clip-rule="evenodd" class="y8r8-nbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:printer-outline" {...props}></Icon>
