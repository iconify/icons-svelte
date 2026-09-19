<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4w_gbbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="g4w_gbbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:openid" {...props}></Icon>
