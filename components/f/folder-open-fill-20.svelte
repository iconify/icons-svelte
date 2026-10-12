<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8_2a_bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b8_2a_bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-open-fill-20" {...props}></Icon>
