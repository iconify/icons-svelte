<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvj_p9b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rvj_p9b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:news-fill" {...props}></Icon>
