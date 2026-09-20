<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1b1yz-3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w1b1yz-3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:plus" {...props}></Icon>
