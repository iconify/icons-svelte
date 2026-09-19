<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e09nf7bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e09nf7bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-import" {...props}></Icon>
