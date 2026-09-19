<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-efg3ywk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<circle class="b-efg3ywk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:armrecording" {...props}></Icon>
