<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1njeob4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1njeob4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader-follow" {...props}></Icon>
