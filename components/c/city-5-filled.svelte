<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi_0iv7qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zi_0iv7qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-5-filled" {...props}></Icon>
