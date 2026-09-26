<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emm7uglhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emm7uglhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bookmark-x-bold" {...props}></Icon>
