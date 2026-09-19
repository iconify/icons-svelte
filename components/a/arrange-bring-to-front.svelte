<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soxy_db2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="soxy_db2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:arrange-bring-to-front" {...props}></Icon>
