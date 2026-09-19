<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld5kc0m-n.css';
import '../../css/x/xfs_8ebyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ld5kc0m-n"/><path class="xfs_8ebyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-skip-back-circle-outline" {...props}></Icon>
