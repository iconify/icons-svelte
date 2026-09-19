<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dda67et_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dda67et_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-haze2-fill" {...props}></Icon>
