<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa5zzd0kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sa5zzd0kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:christian-cross-2-solid" {...props}></Icon>
