<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzkpf5bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzkpf5bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-back-outline" {...props}></Icon>
