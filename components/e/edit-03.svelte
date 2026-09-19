<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oog5nub2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oog5nub2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:edit-03" {...props}></Icon>
