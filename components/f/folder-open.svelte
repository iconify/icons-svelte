<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhkcuob6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lhkcuob6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:folder-open" {...props}></Icon>
