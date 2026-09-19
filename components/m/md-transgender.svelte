<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooioao7bq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ooioao7bq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-transgender" {...props}></Icon>
