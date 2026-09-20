<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzjum0twy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qzjum0twy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:friendica-dark" {...props}></Icon>
