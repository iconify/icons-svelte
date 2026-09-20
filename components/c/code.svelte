<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djxii9bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djxii9bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:code" {...props}></Icon>
