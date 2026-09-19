<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjcg_zb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jjcg_zb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-yml" {...props}></Icon>
