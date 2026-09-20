<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcq5--p3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zcq5--p3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bug-minimalistic-bold" {...props}></Icon>
