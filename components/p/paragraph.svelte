<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz34-ibnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz34-ibnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:paragraph" {...props}></Icon>
