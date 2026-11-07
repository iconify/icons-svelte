<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twg_fi4pi.css';
import '../../css/k/kd5gzltfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twg_fi4pi"/><path class="kd5gzltfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-favorite-bookmark-bold-duotone" {...props}></Icon>
