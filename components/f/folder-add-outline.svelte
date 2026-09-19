<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2nst-b0v.css';
import '../../css/g/gx2betbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2nst-b0v"/><path class="gx2betbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:folder-add-outline" {...props}></Icon>
