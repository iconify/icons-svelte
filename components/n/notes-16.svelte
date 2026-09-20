<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-xld0_tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-xld0_tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:notes-16" {...props}></Icon>
