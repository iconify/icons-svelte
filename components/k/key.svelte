<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_32d92c.css';
import '../../css/x/xmfhvr75a.css';
import '../../css/b/bnvu6ybwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_32d92c"/><path class="xmfhvr75a"/><path class="bnvu6ybwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:key" {...props}></Icon>
