<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgdondpfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jgdondpfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:beach-bag" {...props}></Icon>
