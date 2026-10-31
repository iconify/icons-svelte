<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgxr_vbkp.css';
import '../../css/e/e6hapgbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="dgxr_vbkp"/><path class="e6hapgbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:latvia" {...props}></Icon>
