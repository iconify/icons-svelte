<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bg3g5pbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bg3g5pbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:code-brackets" {...props}></Icon>
