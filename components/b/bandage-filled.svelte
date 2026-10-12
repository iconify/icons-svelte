<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iem8b0w8t.css';
import '../../css/u/uj0j0q9an.css';
import '../../css/y/yy6ac35kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iem8b0w8t"/><path clip-rule="evenodd" class="uj0j0q9an"/><path class="yy6ac35kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bandage-filled" {...props}></Icon>
