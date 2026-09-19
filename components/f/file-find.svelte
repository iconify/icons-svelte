<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtdpz00sp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtdpz00sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-find" {...props}></Icon>
