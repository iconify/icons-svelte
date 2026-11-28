<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztr0zpbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztr0zpbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:baseball-solid" {...props}></Icon>
