<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szmhgzb0a.css';
import '../../css/p/pphqfabzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szmhgzb0a"/><path clip-rule="evenodd" class="pphqfabzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-dot-open-outline" {...props}></Icon>
