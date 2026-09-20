<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfaej_b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zfaej_b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-zip-line" {...props}></Icon>
