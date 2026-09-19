<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrucu7bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1344};
const content = `<path class="lrucu7bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gift" {...props}></Icon>
