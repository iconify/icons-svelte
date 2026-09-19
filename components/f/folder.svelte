<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lat7yg2_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lat7yg2_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder" {...props}></Icon>
