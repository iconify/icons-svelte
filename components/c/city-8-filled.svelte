<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be4mx6bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="be4mx6bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-8-filled" {...props}></Icon>
