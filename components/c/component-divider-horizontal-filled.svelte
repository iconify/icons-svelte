<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny93yw8fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny93yw8fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-divider-horizontal-filled" {...props}></Icon>
