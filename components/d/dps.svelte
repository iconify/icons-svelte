<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9qkw_60r.css';
import '../../css/a/aqfsfgwjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9qkw_60r"/><path class="aqfsfgwjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dps" {...props}></Icon>
