<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmnevccbt.css';
import '../../css/v/vzdhx2clg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmnevccbt"/><path class="vzdhx2clg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-folder-open" {...props}></Icon>
