<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8t-vbbi.css';
import '../../css/b/b_slk7bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="tj8t-vbbi"/><path class="b_slk7bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:leaf-fluttering-in-wind" {...props}></Icon>
