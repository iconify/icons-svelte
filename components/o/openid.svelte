<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf4b38bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf4b38bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:openid" {...props}></Icon>
