<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmv0jrv6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmv0jrv6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:h2" {...props}></Icon>
