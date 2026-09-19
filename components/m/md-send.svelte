<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm3sd0tjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lm3sd0tjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-send" {...props}></Icon>
