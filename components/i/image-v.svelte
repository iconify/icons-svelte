<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtgv8-bzl.css';
import '../../css/v/v4bnoj-6z.css';
import '../../css/i/iturx2siu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtgv8-bzl"/><path class="v4bnoj-6z"/><path class="iturx2siu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:image-v" {...props}></Icon>
