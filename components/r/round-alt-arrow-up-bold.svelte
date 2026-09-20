<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfxbh8bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zfxbh8bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-up-bold" {...props}></Icon>
