<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_asi6lle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s_asi6lle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:dictionary-16" {...props}></Icon>
