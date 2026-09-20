<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt7ztxbrk.css';
import '../../css/k/k-_v8bbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dt7ztxbrk"/><path class="k-_v8bbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hard-disk-storage-filled" {...props}></Icon>
