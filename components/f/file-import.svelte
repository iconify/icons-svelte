<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i32yzb5md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i32yzb5md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:file-import" {...props}></Icon>
