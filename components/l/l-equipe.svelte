<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdv_r9b4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdv_r9b4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:l-equipe" {...props}></Icon>
