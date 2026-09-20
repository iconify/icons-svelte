<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxqkqac6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zxqkqac6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colanode-light" {...props}></Icon>
