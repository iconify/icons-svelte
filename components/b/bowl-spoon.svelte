<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isyk61bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isyk61bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bowl-spoon" {...props}></Icon>
