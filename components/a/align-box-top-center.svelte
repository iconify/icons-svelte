<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blj85pqph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blj85pqph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-top-center" {...props}></Icon>
