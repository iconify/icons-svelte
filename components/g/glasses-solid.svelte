<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc33sp-io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc33sp-io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:glasses-solid" {...props}></Icon>
