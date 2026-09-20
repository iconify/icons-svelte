<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5i3s9bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w5i3s9bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:pod" {...props}></Icon>
