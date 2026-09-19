<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fza6ibbjn.css';
import '../../css/b/bazy2ab2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fza6ibbjn"/><path class="bazy2ab2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-edit-circle-filled" {...props}></Icon>
