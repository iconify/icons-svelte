<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isiz68hyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isiz68hyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:link" {...props}></Icon>
