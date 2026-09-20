<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_8cnqb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v_8cnqb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chair" {...props}></Icon>
