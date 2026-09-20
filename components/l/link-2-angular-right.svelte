<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3irtcyzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="h3irtcyzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:link-2-angular-right" {...props}></Icon>
