<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bngvwn_2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bngvwn_2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:alphabetical-sorting-2" {...props}></Icon>
