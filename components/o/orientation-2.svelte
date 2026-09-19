<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7xfp2n_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f7xfp2n_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:orientation-2" {...props}></Icon>
