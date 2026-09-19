<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv26y9bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bv26y9bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:negative-dynamics" {...props}></Icon>
