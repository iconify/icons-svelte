<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj36z8w0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj36z8w0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:remote-wave" {...props}></Icon>
