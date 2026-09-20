<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkv7bj1bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkv7bj1bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:emby" {...props}></Icon>
