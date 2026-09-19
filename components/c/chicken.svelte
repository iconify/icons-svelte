<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtirc_mzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qtirc_mzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:chicken" {...props}></Icon>
