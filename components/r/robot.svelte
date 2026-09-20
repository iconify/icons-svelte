<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffpxg9b_p.css';
import '../../css/b/b-p4_2b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ffpxg9b_p"/><path class="b-p4_2b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:robot" {...props}></Icon>
