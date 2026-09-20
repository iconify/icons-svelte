<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9eibpubz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9eibpubz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:archway-filled" {...props}></Icon>
