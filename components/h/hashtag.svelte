<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxs_jpr0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cxs_jpr0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:hashtag" {...props}></Icon>
