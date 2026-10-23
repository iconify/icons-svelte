<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2u71zzfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2u71zzfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-plus" {...props}></Icon>
