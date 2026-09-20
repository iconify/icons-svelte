<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjb94vbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjb94vbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-new-outline" {...props}></Icon>
