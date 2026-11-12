<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i104_jbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i104_jbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:it-tools-dark" {...props}></Icon>
