<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc34h_bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="jc34h_bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:paragraph" {...props}></Icon>
