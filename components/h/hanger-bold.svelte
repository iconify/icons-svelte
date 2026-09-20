<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxoozx2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxoozx2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hanger-bold" {...props}></Icon>
