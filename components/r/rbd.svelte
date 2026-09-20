<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh9iygkio.css';
import '../../css/n/ncs9kybml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9iygkio"/><path class="ncs9kybml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rbd" {...props}></Icon>
